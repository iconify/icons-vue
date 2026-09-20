<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8bqi5ahx.css';
import '../../css/c/cq-wbst_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j8bqi5ahx"/><path class="cq-wbst_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:eye-slash" /></template>
