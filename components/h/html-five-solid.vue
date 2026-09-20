<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf0fngu7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sf0fngu7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:html-five-solid" /></template>
