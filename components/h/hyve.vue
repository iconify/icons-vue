<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el-kvbb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el-kvbb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hyve" /></template>
