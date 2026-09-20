<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-uxht4zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h-uxht4zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bug-virus-browser-remix" /></template>
