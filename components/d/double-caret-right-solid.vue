<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waaxqfb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="waaxqfb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:double-caret-right-solid" /></template>
