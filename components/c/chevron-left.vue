<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3qa4ebwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b3qa4ebwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:chevron-left" /></template>
