<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imbpf2bai.css';
import '../../css/e/egbtnbclf.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--alerted clr-i-solid-path-1--alerted imbpf2bai"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-22--alerted egbtnbclf"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:heat-map-solid-alerted" /></template>
