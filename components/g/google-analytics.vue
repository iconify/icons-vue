<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h22y-lv-g.css';
import '../../css/f/fwk_nlbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2195.9,"height":2430.9};
const content = `<path class="h22y-lv-g"/><path class="fwk_nlbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-analytics" /></template>
