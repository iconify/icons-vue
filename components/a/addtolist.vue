<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzo5webma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yzo5webma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:addtolist" /></template>
