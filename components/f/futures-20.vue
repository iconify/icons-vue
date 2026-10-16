<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_38zbbbr.css';
import '../../css/q/qpiu3eb1z.css';
import '../../css/v/vxcokgmud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v_38zbbbr"/><path class="qpiu3eb1z"/><path class="vxcokgmud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:futures-20" /></template>
