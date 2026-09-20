<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwmdc8b7j.css';
import '../../css/y/y5nzee3jx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mwmdc8b7j"/><path class="y5nzee3jx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:file-zip" /></template>
