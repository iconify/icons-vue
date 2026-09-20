<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sosc3bbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sosc3bbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:folder-delete-remix" /></template>
