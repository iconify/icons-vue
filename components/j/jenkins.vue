<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f69hrxcob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f69hrxcob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:jenkins" /></template>
