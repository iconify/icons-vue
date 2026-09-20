<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyy0evbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cyy0evbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:code-block" /></template>
