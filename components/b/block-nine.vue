<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhl620mrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dhl620mrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:block-nine" /></template>
