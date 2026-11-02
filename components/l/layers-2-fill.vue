<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldbsrwxzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldbsrwxzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layers-2-fill" /></template>
