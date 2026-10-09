<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aofe76cbq.css';
import '../../css/g/gxgezbb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aofe76cbq"/><path class="gxgezbb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:interconnector-48-bold" /></template>
