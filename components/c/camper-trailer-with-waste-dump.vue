<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viga7s65v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="viga7s65v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:camper-trailer-with-waste-dump" /></template>
