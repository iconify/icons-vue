<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sav6x4bmf.css';
import '../../css/g/g_gp7lgqe.css';
import '../../css/r/rgr8kdb1y.css';
import '../../css/r/r1dd85yjj.css';
import '../../css/v/v65xh1bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGsBpkoeeA" x1="28.593" x2="16.672" y1="14.226" y2="23.532" gradientTransform="matrix(4 0 0 4 .255 -8.676)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="sav6x4bmf"/><stop offset="1" class="g_gp7lgqe"/></linearGradient></defs><path class="rgr8kdb1y"/><path fill="url(#SVGsBpkoeeA)" class="r1dd85yjj"/><path class="v65xh1bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:bitbucket-wordmark" /></template>
