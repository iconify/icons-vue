<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu-373zuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yu-373zuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:cheese-remix" /></template>
