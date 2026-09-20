<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djqqkvfyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":145,"height":147};
const content = `<path class="djqqkvfyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:alem-tv" /></template>
