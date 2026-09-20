<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd9drcb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":700,"height":294.423};
const content = `<path class="kd9drcb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:disney" /></template>
