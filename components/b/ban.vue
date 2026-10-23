<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqy4i4h1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqy4i4h1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:ban" /></template>
