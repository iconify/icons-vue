<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it330lbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":480};
const content = `<path class="it330lbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:collection-item-1" /></template>
