<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4otqdvpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="k4otqdvpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:folder-open" /></template>
