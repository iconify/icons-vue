<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb1c7ms0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mb1c7ms0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:document-copy" /></template>
