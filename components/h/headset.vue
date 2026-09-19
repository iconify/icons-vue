<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aavcb-bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aavcb-bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:headset" /></template>
