<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/osbldktkr.css';
import '../../css/n/nqmqffbvv.css';
import '../../css/d/dytwysbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="osbldktkr"/><path class="nqmqffbvv"/><path class="dytwysbcm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gamepad-charge-duotone" /></template>
