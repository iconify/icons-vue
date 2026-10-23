<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn_uv_bxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn_uv_bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:battery-low" /></template>
