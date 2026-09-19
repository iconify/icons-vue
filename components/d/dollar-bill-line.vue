<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w96wjlbpj.css';
import '../../css/b/bn68x2b5w.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 w96wjlbpj"/><path class="bn68x2b5w clr-i-outline clr-i-outline-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:dollar-bill-line" /></template>
