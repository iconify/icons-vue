<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb3q4-ebi.css';
import '../../css/h/hf4na_b9p.css';
import '../../css/w/wioby4b9s.css';
import '../../css/r/r7n51--5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":63,"height":64};
const content = `<path class="tb3q4-ebi"/><path class="hf4na_b9p"/><path class="wioby4b9s"/><path class="r7n51--5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-pathology" /></template>
