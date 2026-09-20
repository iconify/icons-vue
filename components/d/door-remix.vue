<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb6-0kbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lb6-0kbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:door-remix" /></template>
