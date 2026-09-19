<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/reyg2abim.css';
import '../../css/j/jsk_qbbtn.css';
import '../../css/k/k6i8m5bia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="reyg2abim"/><path class="jsk_qbbtn"/><path class="k6i8m5bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-calendar" /></template>
