<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv_zncb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gv_zncb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:level-right-bold" /></template>
