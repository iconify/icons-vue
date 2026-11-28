<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqrqgxblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqrqgxblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:folder-open-plus" /></template>
