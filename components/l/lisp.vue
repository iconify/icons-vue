<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp_2e5bqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yp_2e5bqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:lisp" /></template>
