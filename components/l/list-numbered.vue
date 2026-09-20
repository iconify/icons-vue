<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfn7tp2-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfn7tp2-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:list-numbered" /></template>
