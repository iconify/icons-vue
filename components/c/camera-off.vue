<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gojx-tb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gojx-tb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:camera-off" /></template>
