<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk9qdyb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bk9qdyb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:file" /></template>
