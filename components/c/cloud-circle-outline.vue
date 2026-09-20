<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4h578-1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4h578-1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-circle-outline" /></template>
