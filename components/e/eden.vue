<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1sgz3j6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y1sgz3j6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:eden" /></template>
