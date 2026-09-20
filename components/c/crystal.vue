<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1bx12_kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":200,"height":200};
const content = `<path class="v1bx12_kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:crystal" /></template>
