<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_v0keb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="s_v0keb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:arrow-thick-top" /></template>
