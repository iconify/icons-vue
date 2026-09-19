<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwxb-w_rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":14};
const content = `<path class="pwxb-w_rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:dogecoin" /></template>
