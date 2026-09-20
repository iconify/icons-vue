<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2c-w6bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="w2c-w6bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:island" /></template>
