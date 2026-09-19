<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd34l8bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="qd34l8bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:land-mine-on" /></template>
