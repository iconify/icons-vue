<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz4vi98el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":33,"height":33};
const content = `<path class="qz4vi98el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:cucumber" /></template>
