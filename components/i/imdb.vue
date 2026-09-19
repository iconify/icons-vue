<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1xq9pboe.css';
import '../../css/c/cpzpl-ooe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1xq9pboe"/><path class="cpzpl-ooe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:imdb" /></template>
