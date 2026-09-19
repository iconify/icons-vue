<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urh4f7bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="urh4f7bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:magnifier" /></template>
