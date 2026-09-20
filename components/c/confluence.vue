<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs_o-ybdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs_o-ybdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:confluence" /></template>
