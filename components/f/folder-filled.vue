<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u159h1bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u159h1bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:folder-filled" /></template>
