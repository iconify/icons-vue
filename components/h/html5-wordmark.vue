<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2l35xbjn.css';
import '../../css/r/rjff3k7ts.css';
import '../../css/a/as2xfh2ea.css';
import '../../css/z/z-s5yzwsp.css';
import '../../css/t/t_drb30wn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="w2l35xbjn"/><path class="rjff3k7ts"/><path class="as2xfh2ea"/><path class="z-s5yzwsp"/><path class="t_drb30wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:html5-wordmark" /></template>
