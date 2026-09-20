<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/p/p5smuv1fx.css';
import '../../css/i/il0pwlb6n.css';
import '../../css/z/zimgjfjhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><rect transform="rotate(90 9 15)" class="p5smuv1fx"/><path class="il0pwlb6n"/><path class="zimgjfjhx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:line-out-alt" /></template>
