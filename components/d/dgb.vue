<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf6coj27j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lf6coj27j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:dgb" /></template>
