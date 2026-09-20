<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqdtccc3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqdtccc3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:linkwarden" /></template>
