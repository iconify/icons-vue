<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erq5l0bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="erq5l0bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:flow" /></template>
