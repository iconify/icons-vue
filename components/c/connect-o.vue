<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5kb4tbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x5kb4tbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:connect-o" /></template>
