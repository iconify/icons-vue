<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wea8hpbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="wea8hpbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:cloud-outline" /></template>
