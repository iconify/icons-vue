<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqw4e6bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqw4e6bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:craftsman" /></template>
