<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt4uggbee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wt4uggbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:google-plus" /></template>
