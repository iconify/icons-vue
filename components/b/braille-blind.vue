<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uao0u1bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uao0u1bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:braille-blind" /></template>
