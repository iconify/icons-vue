<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfwwvrbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bfwwvrbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-5-bold" /></template>
