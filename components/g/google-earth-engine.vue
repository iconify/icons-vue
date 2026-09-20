<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn1te-lst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn1te-lst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-earth-engine" /></template>
