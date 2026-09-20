<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in1roj-3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="in1roj-3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:cao-dai-remix" /></template>
