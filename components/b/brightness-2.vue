<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj2pfiw1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="aj2pfiw1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:brightness-2" /></template>
