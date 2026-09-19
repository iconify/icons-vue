<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u14sdab1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":397,"height":512};
const content = `<path clip-rule="evenodd" class="u14sdab1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:homebrew" /></template>
