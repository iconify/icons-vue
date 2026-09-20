<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhjziobee.css';
import '../../css/v/vm1oqwb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qhjziobee"/><path class="vm1oqwb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:hands-up" /></template>
