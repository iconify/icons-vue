<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aotw6rd9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aotw6rd9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:hard-hat" /></template>
