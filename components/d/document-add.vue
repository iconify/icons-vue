<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anc5s55-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="anc5s55-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:document-add" /></template>
