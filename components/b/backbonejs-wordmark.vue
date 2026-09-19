<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfrjrd8qn.css';
import '../../css/j/jxfl46bls.css';
import '../../css/h/hfxcmzb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zfrjrd8qn"/><path class="jxfl46bls"/><path class="hfxcmzb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:backbonejs-wordmark" /></template>
