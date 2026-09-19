<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1lsc0bvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t1lsc0bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:arduino" /></template>
