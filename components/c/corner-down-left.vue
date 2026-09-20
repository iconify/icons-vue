<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gml7996sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gml7996sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:corner-down-left" /></template>
