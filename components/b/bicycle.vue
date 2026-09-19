<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue4dzob4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ue4dzob4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bicycle" /></template>
