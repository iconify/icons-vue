<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlsc79brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rlsc79brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:button-stop-remix" /></template>
