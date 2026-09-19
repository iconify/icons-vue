<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmy4l5bds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2016,"height":1664};
const content = `<path class="bmy4l5bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:camel" /></template>
