<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9lsjlp9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n9lsjlp9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:elevator" /></template>
