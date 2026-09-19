<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5rcylbor.css';
import '../../css/u/ua7_yfcga.css';
import '../../css/x/xh51xx53o.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 l5rcylbor"/><path class="clr-i-outline clr-i-outline-path-2 ua7_yfcga"/><circle class="clr-i-outline clr-i-outline-path-3 xh51xx53o"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:help-line" /></template>
