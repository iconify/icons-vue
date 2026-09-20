<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdd_2cbom.css';
import '../../css/e/e-z6fbc7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pdd_2cbom"/><path class="e-z6fbc7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:book-percent" /></template>
