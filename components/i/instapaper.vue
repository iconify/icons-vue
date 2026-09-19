<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3tz-4byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f3tz-4byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:instapaper" /></template>
