<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4nzf6r2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z4nzf6r2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:five" /></template>
