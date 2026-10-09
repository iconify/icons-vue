<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enr033rrc.css';
import '../../css/j/jvpc1i4ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="enr033rrc"/><path class="jvpc1i4ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrows-horizontal-20-bold" /></template>
