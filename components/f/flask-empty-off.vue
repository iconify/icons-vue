<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3dxn9xfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3dxn9xfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flask-empty-off" /></template>
