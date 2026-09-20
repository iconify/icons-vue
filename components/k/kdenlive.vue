<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrg2wkbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrg2wkbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kdenlive" /></template>
