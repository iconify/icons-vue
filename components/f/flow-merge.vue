<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pei8s1mvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pei8s1mvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flow-merge" /></template>
