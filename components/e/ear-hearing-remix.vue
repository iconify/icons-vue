<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb8c3rbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pb8c3rbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ear-hearing-remix" /></template>
