<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaazf3prt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zaazf3prt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-merge-2-fill" /></template>
