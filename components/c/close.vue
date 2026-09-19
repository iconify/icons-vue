<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0dxmwn6y.css';
import '../../css/h/h6dm1v_wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0dxmwn6y"/><path class="h6dm1v_wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:close" /></template>
