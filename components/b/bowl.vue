<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh3b75c1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="xh3b75c1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bowl" /></template>
