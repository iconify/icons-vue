<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb90-ob5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kb90-ob5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:hand" /></template>
