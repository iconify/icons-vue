<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aadn1wbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="aadn1wbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:layers-1" /></template>
