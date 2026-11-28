<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b918jacqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="b918jacqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:folder-check-thin" /></template>
