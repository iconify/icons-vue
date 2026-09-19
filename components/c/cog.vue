<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkd9qz5fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="pkd9qz5fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:cog" /></template>
