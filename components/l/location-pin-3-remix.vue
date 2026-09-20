<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbpt-4e8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kbpt-4e8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:location-pin-3-remix" /></template>
