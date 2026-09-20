<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-hq2_bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y-hq2_bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:blind-solid" /></template>
