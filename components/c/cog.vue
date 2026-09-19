<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh0sdu0jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fh0sdu0jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:cog" /></template>
