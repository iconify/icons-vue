<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nebj-zb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nebj-zb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-bold" /></template>
