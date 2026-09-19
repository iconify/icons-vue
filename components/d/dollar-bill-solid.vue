<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj3_baclh.css';
import '../../css/a/a0_d2850p.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 mj3_baclh"/><ellipse class="a0_d2850p clr-i-solid clr-i-solid-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:dollar-bill-solid" /></template>
