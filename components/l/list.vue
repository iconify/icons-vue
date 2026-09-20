<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gutb4rbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gutb4rbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:list" /></template>
