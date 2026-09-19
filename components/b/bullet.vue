<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtxu6e6hc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="wtxu6e6hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bullet" /></template>
