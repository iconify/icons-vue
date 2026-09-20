<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1mn4yb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e1mn4yb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:laptop" /></template>
