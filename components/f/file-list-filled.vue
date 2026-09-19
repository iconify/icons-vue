<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7bd_7bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u7bd_7bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:file-list-filled" /></template>
