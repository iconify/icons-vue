<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpk_fgauq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bpk_fgauq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:gavel" /></template>
