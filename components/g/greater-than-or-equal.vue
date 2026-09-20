<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vma9j-bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vma9j-bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:greater-than-or-equal" /></template>
