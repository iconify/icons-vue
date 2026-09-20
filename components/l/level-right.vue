<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8o-nvzdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v8o-nvzdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:level-right" /></template>
