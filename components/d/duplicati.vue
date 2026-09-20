<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y02t58mry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y02t58mry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:duplicati" /></template>
