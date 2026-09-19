<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj-ptsmyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj-ptsmyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:color-fill" /></template>
