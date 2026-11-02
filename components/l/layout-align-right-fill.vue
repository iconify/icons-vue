<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1fzww7tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1fzww7tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-align-right-fill" /></template>
