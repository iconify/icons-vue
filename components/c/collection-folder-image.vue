<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4ecrjb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":432};
const content = `<path class="j4ecrjb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:collection-folder-image" /></template>
