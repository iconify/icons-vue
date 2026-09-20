<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eud5tvbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eud5tvbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:align-left-1-remix" /></template>
