<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne_11cc-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ne_11cc-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:diamond-three" /></template>
