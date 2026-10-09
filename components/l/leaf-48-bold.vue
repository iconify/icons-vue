<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3hcjybun.css';
import '../../css/s/sq0k58bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r3hcjybun"/><path class="sq0k58bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:leaf-48-bold" /></template>
