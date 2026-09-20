<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn-w9f_5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yn-w9f_5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:factory-2-fill" /></template>
