<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7mkxxbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7mkxxbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drama-line" /></template>
