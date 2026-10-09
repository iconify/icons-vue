<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrdv28bdf.css';
import '../../css/v/vceel18zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mrdv28bdf"/><path class="vceel18zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:alert-octagon-20" /></template>
