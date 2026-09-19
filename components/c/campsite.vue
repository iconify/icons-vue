<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4n6sib-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f4n6sib-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:campsite" /></template>
