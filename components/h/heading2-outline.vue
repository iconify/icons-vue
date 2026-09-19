<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc_nmfe2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc_nmfe2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:heading2-outline" /></template>
