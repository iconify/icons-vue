<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zfea1w8pd.css';
import '../../css/e/ec2n0sbxz.css';
import '../../css/r/r16u45bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zfea1w8pd"/><path class="ec2n0sbxz"/><path class="r16u45bjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cupcake-duotone" /></template>
