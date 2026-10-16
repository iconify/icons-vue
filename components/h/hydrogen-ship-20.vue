<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_z7uitjb.css';
import '../../css/v/v2u1wbcfd.css';
import '../../css/t/tvp2jabtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k_z7uitjb"/><path class="v2u1wbcfd"/><path class="tvp2jabtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-ship-20" /></template>
