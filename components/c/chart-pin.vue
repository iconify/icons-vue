<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lwnrebcsd.css';
import '../../css/q/q1se71oae.css';
import '../../css/g/galbvhezo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lwnrebcsd"/><path class="q1se71oae"/><circle class="galbvhezo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:chart-pin" /></template>
