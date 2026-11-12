<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hizqcsbyt.css';
import '../../css/x/xsfw_6dos.css';
import '../../css/y/yvtc_v5-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hizqcsbyt"/><path class="xsfw_6dos"/><path class="yvtc_v5-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:fluxcd" /></template>
