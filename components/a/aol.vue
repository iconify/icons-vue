<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv02enbhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wv02enbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aol" /></template>
