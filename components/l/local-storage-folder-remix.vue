<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1qgo2r7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g1qgo2r7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:local-storage-folder-remix" /></template>
