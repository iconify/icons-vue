<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwf0vrgqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="wwf0vrgqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-round-up-left" /></template>
