<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6q3qci0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b6q3qci0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:airplane-mode-off" /></template>
