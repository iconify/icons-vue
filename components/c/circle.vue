<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9jtn9bji.css';
import '../../css/j/j5hqbks0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9jtn9bji"/><path class="j5hqbks0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:circle" /></template>
