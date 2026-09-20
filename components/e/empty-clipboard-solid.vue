<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzks0db6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nzks0db6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:empty-clipboard-solid" /></template>
