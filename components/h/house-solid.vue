<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw3qv_-pu.css';
import '../../css/f/fmh8adbaz.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 hw3qv_-pu"/><path class="clr-i-solid clr-i-solid-path-2 fmh8adbaz"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:house-solid" /></template>
