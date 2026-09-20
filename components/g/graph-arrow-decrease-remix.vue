<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojyj0msue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ojyj0msue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:graph-arrow-decrease-remix" /></template>
