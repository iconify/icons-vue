<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mev5h9d-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mev5h9d-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:archive-arrow-down" /></template>
