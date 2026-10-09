<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwp3j2jcs.css';
import '../../css/k/k_v0rcc0n.css';
import '../../css/u/usnws24vp.css';
import '../../css/b/bksa0ub5k.css';
import '../../css/f/fy4c6vbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uwp3j2jcs"/><path class="k_v0rcc0n"/><path class="usnws24vp"/><path class="bksa0ub5k"/><path class="fy4c6vbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-solar-48" /></template>
