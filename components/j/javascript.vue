<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vieqjxhro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vieqjxhro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:javascript" /></template>
