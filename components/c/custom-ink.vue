<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7fec_l4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7fec_l4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:custom-ink" /></template>
