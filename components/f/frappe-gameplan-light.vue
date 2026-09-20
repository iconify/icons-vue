<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwmmrrb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bwmmrrb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-gameplan-light" /></template>
