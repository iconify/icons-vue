<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sahn3db4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="sahn3db4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:code-pull-request" /></template>
