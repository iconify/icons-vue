<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skiiyvb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="skiiyvb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:basketball-stroke-12" /></template>
