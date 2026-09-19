<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubs-d4r4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ubs-d4r4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:chevron-circle-up" /></template>
