<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm4c3kbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm4c3kbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bug" /></template>
