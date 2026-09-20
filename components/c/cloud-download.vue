<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3rq8j5si.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b3rq8j5si"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:cloud-download" /></template>
