<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwqm53jlt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lwqm53jlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:jade" /></template>
