<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/taqnhk4cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="taqnhk4cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:hackerrank" /></template>
