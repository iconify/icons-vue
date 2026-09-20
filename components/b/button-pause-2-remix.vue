<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_mbj4-zo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r_mbj4-zo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:button-pause-2-remix" /></template>
