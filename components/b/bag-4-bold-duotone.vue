<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpptw4brn.css';
import '../../css/f/fq3gxbred.css';
import '../../css/e/ec8ku5buv.css';
import '../../css/w/wr7qp9b-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpptw4brn"/><path class="fq3gxbred"/><path class="ec8ku5buv"/><path class="wr7qp9b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-4-bold-duotone" /></template>
