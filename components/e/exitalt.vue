<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxa4qxbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="jxa4qxbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:exitalt" /></template>
