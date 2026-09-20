<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-l9itbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l-l9itbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:insert-top-left-remix" /></template>
