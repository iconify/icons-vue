<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iagiy7bpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="iagiy7bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:collection-bookmark" /></template>
