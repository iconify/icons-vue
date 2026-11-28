<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqiuh1juc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="uqiuh1juc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bee-light" /></template>
