<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkvmp3jov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fkvmp3jov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:button-fast-forward-2-solid" /></template>
