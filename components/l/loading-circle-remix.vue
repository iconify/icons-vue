<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7sni-u8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y7sni-u8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:loading-circle-remix" /></template>
