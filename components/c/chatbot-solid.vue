<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhuikybji.css';
import '../../css/s/s3hbfpb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xhuikybji"/><path clip-rule="evenodd" class="s3hbfpb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:chatbot-solid" /></template>
