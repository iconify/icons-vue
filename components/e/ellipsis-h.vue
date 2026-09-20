<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q713wstdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q713wstdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:ellipsis-h" /></template>
