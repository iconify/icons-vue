<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oppq-ug0u.css';
import '../../css/l/l-_13j-ie.css';
import '../../css/n/nr6pp78hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oppq-ug0u"/><path class="l-_13j-ie"/><path class="nr6pp78hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:borehole-48-bold" /></template>
