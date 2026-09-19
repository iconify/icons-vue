<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzbnv-3ul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="kzbnv-3ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:file-word" /></template>
