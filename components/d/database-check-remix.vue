<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg8w7gxvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eg8w7gxvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:database-check-remix" /></template>
