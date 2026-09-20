<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bva9_bcop.css';
import '../../css/m/mkzt5foon.css';
import '../../css/h/h5vc_wttc.css';
import '../../css/n/n7mdeobel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bva9_bcop"/><path class="mkzt5foon"/><path class="h5vc_wttc"/><path class="n7mdeobel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:flip-h" /></template>
