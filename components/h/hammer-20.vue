<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7a1zgbqk.css';
import '../../css/d/d_mc1ovfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e7a1zgbqk"/><path class="d_mc1ovfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hammer-20" /></template>
