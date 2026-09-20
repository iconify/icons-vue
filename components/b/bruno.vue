<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyzb7jb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyzb7jb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bruno" /></template>
