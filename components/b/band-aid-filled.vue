<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvnxf2gox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvnxf2gox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:band-aid-filled" /></template>
