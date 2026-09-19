<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib9hyvbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":632};
const content = `<path class="ib9hyvbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:folder" /></template>
