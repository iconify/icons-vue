<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyyddszli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yyyddszli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:girl-sad" /></template>
