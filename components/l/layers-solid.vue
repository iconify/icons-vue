<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj8lr2bdq.css';
import '../../css/c/c6ggvk-4f.css';
import '../../css/m/m2qp7_pyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hj8lr2bdq"/><path class="c6ggvk-4f"/><path class="m2qp7_pyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:layers-solid" /></template>
