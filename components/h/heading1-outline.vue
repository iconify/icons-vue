<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoxiukb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uoxiukb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:heading1-outline" /></template>
