<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bixh1wb9y.css';
import '../../css/h/hzjf5hkxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bixh1wb9y"/><path class="hzjf5hkxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:draught-proofing-20-bold" /></template>
