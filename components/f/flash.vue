<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miodk4bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="miodk4bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:flash" /></template>
