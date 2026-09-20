<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lurx8abhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lurx8abhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:delete-1-filled" /></template>
