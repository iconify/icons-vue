<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/na63v48uc.css';
import '../../css/l/lnd3c0bpx.css';
import '../../css/r/rk3zggbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="na63v48uc"/><path class="lnd3c0bpx"/><path class="rk3zggbju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:desk-alt-duotone" /></template>
