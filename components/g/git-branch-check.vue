<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/temj2-uou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="temj2-uou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:git-branch-check" /></template>
