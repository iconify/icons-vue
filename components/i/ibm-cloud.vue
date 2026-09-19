<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiibf2oyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eiibf2oyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud" /></template>
