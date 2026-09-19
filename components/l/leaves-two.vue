<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs9a_6gej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fs9a_6gej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:leaves-two" /></template>
