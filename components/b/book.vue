<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gypgt4b0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":512};
const content = `<path class="gypgt4b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:book" /></template>
