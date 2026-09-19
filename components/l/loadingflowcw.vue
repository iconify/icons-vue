<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll5l_dukg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ll5l_dukg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:loadingflowcw" /></template>
