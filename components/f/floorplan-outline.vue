<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot78e65or.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ot78e65or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:floorplan-outline" /></template>
