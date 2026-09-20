<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l41g2w51k.css';
import '../../css/w/w98s6ebmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="l41g2w51k"/><path class="w98s6ebmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:cross-country-skiing" /></template>
