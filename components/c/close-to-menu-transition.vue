<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmz6kf.css';
import '../../css/d/d-jarxnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmz6kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:close-to-menu-transition" /></template>
