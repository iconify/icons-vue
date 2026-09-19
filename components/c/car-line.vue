<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cslm94z5v.css';
import '../../css/i/is1vivbaq.css';
import '../../css/w/w1u9r841l.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 cslm94z5v"/><path class="clr-i-outline clr-i-outline-path-2 is1vivbaq"/><path class="clr-i-outline clr-i-outline-path-3 w1u9r841l"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:car-line" /></template>
