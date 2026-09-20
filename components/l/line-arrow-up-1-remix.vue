<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o900hie1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o900hie1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-up-1-remix" /></template>
