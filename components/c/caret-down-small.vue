<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfhl96tbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfhl96tbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:caret-down-small" /></template>
