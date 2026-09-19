<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9zceibib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x9zceibib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:gift-fill" /></template>
