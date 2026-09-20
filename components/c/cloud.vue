<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk8ejyb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lk8ejyb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:cloud" /></template>
