<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbj8p3c7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qbj8p3c7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:file-check" /></template>
