<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls3gd3b9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ls3gd3b9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:h2" /></template>
