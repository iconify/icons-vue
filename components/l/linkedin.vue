<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7p34wbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="q7p34wbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:linkedin" /></template>
