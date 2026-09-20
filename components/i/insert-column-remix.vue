<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-cop6swr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="z-cop6swr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:insert-column-remix" /></template>
