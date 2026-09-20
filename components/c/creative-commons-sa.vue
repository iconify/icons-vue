<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onqq3ib-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="onqq3ib-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:creative-commons-sa" /></template>
