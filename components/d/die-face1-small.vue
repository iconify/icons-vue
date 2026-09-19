<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v46coki7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="v46coki7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:die-face1-small" /></template>
