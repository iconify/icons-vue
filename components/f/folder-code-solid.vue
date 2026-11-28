<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm85orbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm85orbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-code-solid" /></template>
