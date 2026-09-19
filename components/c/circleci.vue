<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6audjk_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q6audjk_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:circleci" /></template>
