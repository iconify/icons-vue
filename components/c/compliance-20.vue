<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-myk9bcg.css';
import '../../css/f/fc_ybimmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a-myk9bcg"/><path class="fc_ybimmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:compliance-20" /></template>
