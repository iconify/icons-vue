<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbr64l8xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbr64l8xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:500px" /></template>
