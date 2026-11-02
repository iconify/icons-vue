<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py38cvbqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py38cvbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:documents-line" /></template>
