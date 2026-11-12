<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf020ifmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yf020ifmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docuseal" /></template>
