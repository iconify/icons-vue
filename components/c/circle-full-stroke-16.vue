<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqoqyjb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<circle class="xqoqyjb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:circle-full-stroke-16" /></template>
