<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7upw-bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7upw-bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:github-outline" /></template>
