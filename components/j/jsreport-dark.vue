<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnxapn8mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hnxapn8mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jsreport-dark" /></template>
