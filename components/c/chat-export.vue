<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm-ndgzjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jm-ndgzjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:chat-export" /></template>
