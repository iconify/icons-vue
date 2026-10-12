<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_4nbxblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f_4nbxblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bold-20" /></template>
