<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf0bu9bgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="wf0bu9bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:draft2digital" /></template>
