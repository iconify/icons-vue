<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itbt_h6ys.css';
import '../../css/o/o5ayvslgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="itbt_h6ys"/><path class="o5ayvslgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:area-select" /></template>
