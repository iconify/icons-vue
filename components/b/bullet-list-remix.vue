<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4rmx3eua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n4rmx3eua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bullet-list-remix" /></template>
