<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc-4xxsbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="lc-4xxsbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:devices" /></template>
