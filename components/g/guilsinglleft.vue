<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuiynvcqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":516,"height":614};
const content = `<path class="kuiynvcqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:guilsinglleft" /></template>
