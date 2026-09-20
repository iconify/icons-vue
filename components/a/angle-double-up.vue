<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a33b94myo.css';
import '../../css/o/o08jojm8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a33b94myo"/><path class="o08jojm8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:angle-double-up" /></template>
