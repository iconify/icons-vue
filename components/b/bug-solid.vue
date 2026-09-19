<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1o7njy2n.css';
import '../../css/l/l8ou0_wvg.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 q1o7njy2n"/><path class="clr-i-solid clr-i-solid-path-2 l8ou0_wvg"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:bug-solid" /></template>
