<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgk6z6b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bgk6z6b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:eye-closed" /></template>
