<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clo7jz9rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="clo7jz9rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:boots" /></template>
