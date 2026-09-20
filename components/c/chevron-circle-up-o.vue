<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5o--747c.css';
import '../../css/x/xcy-b-u_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l5o--747c"/><path class="xcy-b-u_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:chevron-circle-up-o" /></template>
