<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0ofe3bdn.css';
import '../../css/o/o8y0g9bld.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 o0ofe3bdn"/><path class="clr-i-outline clr-i-outline-path-2 o8y0g9bld"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:ferry-line" /></template>
