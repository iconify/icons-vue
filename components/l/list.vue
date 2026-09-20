<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zztq-cb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zztq-cb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:list" /></template>
