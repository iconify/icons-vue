<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnzeedbwl.css';
import '../../css/s/s1c9mbcsk.css';
import '../../css/k/kcqns6e2b.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 dnzeedbwl"/><path class="clr-i-solid clr-i-solid-path-2 s1c9mbcsk"/><path class="clr-i-solid clr-i-solid-path-3 kcqns6e2b"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:hourglass-solid" /></template>
