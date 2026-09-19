<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4d54nbgi.css';
import '../../css/n/nvnb2yl3l.css';
import '../../css/s/s164q9ezg.css';
import '../../css/s/s6ol5ccju.css';
import '../../css/j/j5lzypbjv.css';
import '../../css/k/kea0dyb4k.css';
import '../../css/o/oq7lg2blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d4d54nbgi"/><path class="nvnb2yl3l"/><path class="s164q9ezg"/><path class="s6ol5ccju"/><path class="j5lzypbjv"/><circle class="kea0dyb4k"/><path class="oq7lg2blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:framewithpicture" /></template>
