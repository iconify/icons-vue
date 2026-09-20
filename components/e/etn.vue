<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8ct9jb7j.css';
import '../../css/f/f77eelu2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8ct9jb7j"/><path class="f77eelu2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:etn" /></template>
