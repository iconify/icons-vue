<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2ffrbbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="l2ffrbbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:folder-add" /></template>
