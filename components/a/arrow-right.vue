<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xalh2vdwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xalh2vdwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate-color:arrow-right" /></template>
