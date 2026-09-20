<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yeef006fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="yeef006fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:asterisk-1" /></template>
