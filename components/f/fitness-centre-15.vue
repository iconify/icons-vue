<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8frt8zje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o8frt8zje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:fitness-centre-15" /></template>
