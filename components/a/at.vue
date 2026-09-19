<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl5kxt80y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl5kxt80y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:at" /></template>
