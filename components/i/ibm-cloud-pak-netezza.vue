<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufa-0g21i.css';
import '../../css/a/a_-4bw6-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ufa-0g21i"/><path class="a_-4bw6-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-pak-netezza" /></template>
