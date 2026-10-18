<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv2slsbxu.css';
import '../../css/g/glkalfxwv.css';
import '../../css/y/ywpb2n2bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uv2slsbxu"/><path class="glkalfxwv"/><path class="ywpb2n2bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hi-vis-vest-20-bold" /></template>
