<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxl-uqb-c.css';
import '../../css/g/g5vhpfb4s.css';
import '../../css/e/ezxbjlbqv.css';
import '../../css/e/e9imb0b3j.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="clr-i-solid clr-i-solid-path-1 dxl-uqb-c"/><path class="clr-i-solid clr-i-solid-path-2 g5vhpfb4s"/><path class="clr-i-solid clr-i-solid-path-3 ezxbjlbqv"/><path class="clr-i-solid clr-i-solid-path-4 e9imb0b3j"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:id-badge-solid" /></template>
