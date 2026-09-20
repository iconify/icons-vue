<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5oj8v8lj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o5oj8v8lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ice-cream-2-fill" /></template>
