<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cksjdsb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cksjdsb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:attribution-remix" /></template>
