<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/u/umi_lsbuk.css';
import '../../css/r/r93eu13-n.css';
import '../../css/r/ryl82g88k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="umi_lsbuk"/><path class="r93eu13-n"/><path class="ryl82g88k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:account-recovery" /></template>
