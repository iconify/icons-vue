<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/houilkbik.css';
import '../../css/h/h8mlz4ctj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="houilkbik"/><rect class="h8mlz4ctj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:clipboard-fill" /></template>
