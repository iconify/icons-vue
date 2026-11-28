<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crt23cceo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="crt23cceo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:chat-plus-thin" /></template>
