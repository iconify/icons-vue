<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o94mocbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o94mocbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hungry-jack-s" /></template>
