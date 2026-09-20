<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru8eoqtct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ru8eoqtct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apostrophecms-dark" /></template>
