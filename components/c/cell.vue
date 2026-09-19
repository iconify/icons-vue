<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vybawutoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="vybawutoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cell" /></template>
