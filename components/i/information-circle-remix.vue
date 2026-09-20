<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g561d8b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="g561d8b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:information-circle-remix" /></template>
