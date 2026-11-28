<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr7e56b9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr7e56b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:first-aid-check" /></template>
