<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwzh4kbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwzh4kbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:code" /></template>
