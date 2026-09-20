<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdk53skdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdk53skdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:article-line" /></template>
