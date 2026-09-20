<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6xi-86mu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x6xi-86mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:layout-window-2-solid" /></template>
