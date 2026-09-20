<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy4k87b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy4k87b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-filter-centre-focus-weak" /></template>
