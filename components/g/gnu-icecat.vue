<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f07l8cl4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f07l8cl4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gnu-icecat" /></template>
