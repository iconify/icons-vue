<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg0gy_r-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg0gy_r-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:donation" /></template>
