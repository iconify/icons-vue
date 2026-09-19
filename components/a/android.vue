<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f494_fepc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1664};
const content = `<path class="f494_fepc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:android" /></template>
