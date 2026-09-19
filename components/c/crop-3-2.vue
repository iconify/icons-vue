<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm-v76dnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="sm-v76dnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:crop-3-2" /></template>
