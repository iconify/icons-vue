<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdbru3nfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1664};
const content = `<path class="tdbru3nfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:flash" /></template>
