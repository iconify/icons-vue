<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp-u-h4-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tp-u-h4-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:brightness-1-remix" /></template>
