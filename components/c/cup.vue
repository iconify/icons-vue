<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsth7bq1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":800};
const content = `<path class="hsth7bq1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:cup" /></template>
