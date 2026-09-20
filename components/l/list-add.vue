<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6433eekj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v6433eekj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:list-add" /></template>
