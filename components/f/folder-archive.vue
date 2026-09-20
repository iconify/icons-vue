<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlovhpv6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tlovhpv6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:folder-archive" /></template>
