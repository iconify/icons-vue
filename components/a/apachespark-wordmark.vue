<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww53_jbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ww53_jbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:apachespark-wordmark" /></template>
