<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf1u95bfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nf1u95bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-left-ellipsis-16-solid" /></template>
