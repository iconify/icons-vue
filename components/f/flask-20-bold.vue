<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkj27_b_o.css';
import '../../css/y/yhsrnr9wa.css';
import '../../css/w/w-lq_-7kx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vkj27_b_o"/><path class="yhsrnr9wa"/><path class="w-lq_-7kx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flask-20-bold" /></template>
