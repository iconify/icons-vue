<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj-fh3btt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj-fh3btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-horizontal-fill" /></template>
