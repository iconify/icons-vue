<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0_qlsbau.css';
import '../../css/n/nsxqd3bqb.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 x0_qlsbau"/><path class="clr-i-outline clr-i-outline-path-2 nsxqd3bqb"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:lock-line" /></template>
