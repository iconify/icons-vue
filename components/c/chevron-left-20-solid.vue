<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb7zqp66w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jb7zqp66w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-left-20-solid" /></template>
