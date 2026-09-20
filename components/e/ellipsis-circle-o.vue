<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd_9zuben.css';
import '../../css/g/g0ffiyboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vd_9zuben"/><path class="g0ffiyboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:ellipsis-circle-o" /></template>
