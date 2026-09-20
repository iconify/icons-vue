<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv5foobii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv5foobii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:check-circle-fill" /></template>
