<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u58tcab0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u58tcab0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:chessdotcom" /></template>
