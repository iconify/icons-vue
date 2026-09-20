<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgalthvnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgalthvnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:drawer-envelope-bold" /></template>
