<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu2b7hb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nu2b7hb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:google-plus" /></template>
