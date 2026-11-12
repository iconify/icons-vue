<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu0ejsbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gu0ejsbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:blinko-dark" /></template>
