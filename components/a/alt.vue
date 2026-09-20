<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6wlm125p.css';
import '../../css/m/m2_snib1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o6wlm125p"/><path class="m2_snib1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:alt" /></template>
