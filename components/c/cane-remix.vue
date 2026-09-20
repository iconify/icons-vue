<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b570ztgps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b570ztgps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cane-remix" /></template>
