<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxjz801rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxjz801rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:dxc" /></template>
