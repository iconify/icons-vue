<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plarn4fbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="plarn4fbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:angle-left" /></template>
