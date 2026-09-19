<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0si7bc9c.css';
import '../../css/r/r-xntnbat.css';
import '../../css/l/lq-q1ngth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="m0si7bc9c"/><rect class="r-xntnbat"/><path class="lq-q1ngth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:align-vertical-justify-center-filled" /></template>
