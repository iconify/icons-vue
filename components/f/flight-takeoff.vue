<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7b5ovbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y7b5ovbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:flight-takeoff" /></template>
