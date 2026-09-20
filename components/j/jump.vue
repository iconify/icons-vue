<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf4j0wbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf4j0wbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:jump" /></template>
