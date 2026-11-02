<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm_8amnbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm_8amnbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-up-2-line" /></template>
