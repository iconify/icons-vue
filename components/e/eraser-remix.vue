<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcmp-5byw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zcmp-5byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:eraser-remix" /></template>
