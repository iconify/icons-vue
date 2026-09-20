<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkvn7i82x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zkvn7i82x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:keyboard-remix" /></template>
