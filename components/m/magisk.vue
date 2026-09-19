<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp4a3ib0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cp4a3ib0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:magisk" /></template>
