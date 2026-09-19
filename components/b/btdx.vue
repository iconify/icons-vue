<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5eou4ady.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s5eou4ady"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:btdx" /></template>
