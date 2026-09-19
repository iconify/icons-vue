<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skkkx6ncv.css';
import '../../css/o/ors_3pbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="skkkx6ncv"/><path class="ors_3pbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-reverse-fill-12" /></template>
