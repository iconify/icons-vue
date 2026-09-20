<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzxji-0-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gzxji-0-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:device-fan" /></template>
