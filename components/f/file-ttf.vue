<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo8ud7_4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mo8ud7_4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-ttf" /></template>
