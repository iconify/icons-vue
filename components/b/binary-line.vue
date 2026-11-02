<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk2lv00-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk2lv00-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:binary-line" /></template>
