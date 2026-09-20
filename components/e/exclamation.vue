<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffqs8ektl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ffqs8ektl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:exclamation" /></template>
