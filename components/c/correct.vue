<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh3sju-sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rh3sju-sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:correct" /></template>
