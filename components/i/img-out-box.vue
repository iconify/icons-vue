<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v5zvm9q9e.css';
import '../../css/u/u-fcgxbzx.css';
import '../../css/e/e7ble4bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v5zvm9q9e"/><path clip-rule="evenodd" class="u-fcgxbzx"/><path class="e7ble4bav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:img-out-box" /></template>
