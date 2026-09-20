<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oulhdmbyw.css';
import '../../css/i/iuiai5bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oulhdmbyw"/><path class="iuiai5bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:git-commit-1-filled" /></template>
