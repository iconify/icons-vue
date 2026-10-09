<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yajgwt04s.css';
import '../../css/l/l5wk8zbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yajgwt04s"/><path class="l5wk8zbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:forecast-20" /></template>
