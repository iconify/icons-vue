<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oods8obzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oods8obzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:envelope-upload-alt" /></template>
