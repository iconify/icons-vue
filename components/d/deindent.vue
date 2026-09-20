<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb8cwrcqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pb8cwrcqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:deindent" /></template>
