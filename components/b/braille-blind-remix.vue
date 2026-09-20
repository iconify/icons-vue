<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezsce_bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ezsce_bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:braille-blind-remix" /></template>
