<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/temjivdtd.css';
import '../../css/x/xsit_hb8q.css';
import '../../css/c/cj87lbbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="temjivdtd"/><path class="xsit_hb8q"/><path class="cj87lbbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-personadd-outline" /></template>
