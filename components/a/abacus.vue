<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtz71fwrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qtz71fwrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:abacus" /></template>
