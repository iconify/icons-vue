<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go1mctbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go1mctbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-minus-fill" /></template>
