<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oku0v98jv.css';
import '../../css/l/l93gu5f2n.css';
import '../../css/o/o23se-ntx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oku0v98jv"/><path class="l93gu5f2n"/><path class="o23se-ntx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lighthouse-20" /></template>
