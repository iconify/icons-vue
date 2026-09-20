<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjso1ccoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bjso1ccoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:align-right-1-remix" /></template>
