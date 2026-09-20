<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wii_33l7g.css';
import '../../css/z/z05w6h9vf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wii_33l7g"/><path class="z05w6h9vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:dialogflow" /></template>
