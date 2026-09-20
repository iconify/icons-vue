<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qphvnvb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qphvnvb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:chevron-left-small" /></template>
