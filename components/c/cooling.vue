<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysj6xpb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ysj6xpb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cooling" /></template>
