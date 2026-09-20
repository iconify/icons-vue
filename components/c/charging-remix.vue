<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmyi_m26e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jmyi_m26e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:charging-remix" /></template>
