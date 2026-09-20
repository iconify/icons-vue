<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrpu6pbds.css';
import '../../css/r/rw33ohb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nrpu6pbds"/><path class="rw33ohb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:google-plus-square" /></template>
