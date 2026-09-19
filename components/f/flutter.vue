<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiskk2quo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xiskk2quo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:flutter" /></template>
