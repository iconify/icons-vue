<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf562yesk.css';
import '../../css/c/cnej8nbnf.css';
import '../../css/g/gkd3fq_9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gf562yesk"/><path class="cnej8nbnf"/><path class="gkd3fq_9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:capacitor-runtime" /></template>
