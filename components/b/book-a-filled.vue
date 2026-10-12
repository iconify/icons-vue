<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yts5iln8l.css';
import '../../css/d/d4f-gldbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yts5iln8l"/><path clip-rule="evenodd" class="d4f-gldbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:book-a-filled" /></template>
