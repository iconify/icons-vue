<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsp_xm4zv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsp_xm4zv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:drawer" /></template>
