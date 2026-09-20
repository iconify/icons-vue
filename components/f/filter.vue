<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b74u6lyni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b74u6lyni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:filter" /></template>
