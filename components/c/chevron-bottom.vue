<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd24wbb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sd24wbb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:chevron-bottom" /></template>
