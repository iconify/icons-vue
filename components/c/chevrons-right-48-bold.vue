<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grgrw979e.css';
import '../../css/w/wu8h8ib5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="grgrw979e"/><path class="wu8h8ib5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-right-48-bold" /></template>
