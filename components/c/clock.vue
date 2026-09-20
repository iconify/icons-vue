<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mabwzbbvc.css';
import '../../css/a/a1sqeabop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mabwzbbvc"/><path class="a1sqeabop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:clock" /></template>
