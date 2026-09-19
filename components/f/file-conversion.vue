<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km1zm6hiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="km1zm6hiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:file-conversion" /></template>
