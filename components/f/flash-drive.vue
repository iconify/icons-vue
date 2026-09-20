<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh0zqjb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh0zqjb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:flash-drive" /></template>
