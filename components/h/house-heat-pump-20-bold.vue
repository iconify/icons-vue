<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1mcems0k.css';
import '../../css/d/dp_h2wb9o.css';
import '../../css/b/bcklhmbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1mcems0k"/><path class="dp_h2wb9o"/><path class="bcklhmbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-heat-pump-20-bold" /></template>
