<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up02t5b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="up02t5b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:css-three-remix" /></template>
