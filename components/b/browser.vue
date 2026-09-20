<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3gebbbqf.css';
import '../../css/c/cipl_2bab.css';
import '../../css/r/r5j0fgdnc.css';
import '../../css/w/wslm_vb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<ellipse class="d3gebbbqf"/><path class="cipl_2bab"/><ellipse class="r5j0fgdnc"/><path class="wslm_vb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:browser" /></template>
