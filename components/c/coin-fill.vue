<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw3pupb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rw3pupb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:coin-fill" /></template>
