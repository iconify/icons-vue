<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i66_yd2fa.css';
import '../../css/o/o-bsg_b-e.css';
import '../../css/h/hayl1lfmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i66_yd2fa"/><path class="o-bsg_b-e"/><path class="hayl1lfmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-minus-20-bold" /></template>
