<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8y7-zbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n8y7-zbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dazn-light" /></template>
