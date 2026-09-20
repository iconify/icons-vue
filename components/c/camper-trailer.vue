<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy_tt7b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gy_tt7b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:camper-trailer" /></template>
