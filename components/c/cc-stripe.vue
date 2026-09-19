<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yui9tm2fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1536};
const content = `<path class="yui9tm2fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:cc-stripe" /></template>
