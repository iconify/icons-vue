<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2z29zb9a.css';
import '../../css/z/zylob-b1v.css';
import '../../css/m/m_g9cerbk.css';
import '../../css/m/m0gubtb5o.css';
import '../../css/b/brnj5ubbo.css';
import '../../css/j/jkpms2b3a.css';
import '../../css/n/nmv-rksiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<circle class="a2z29zb9a"/><path class="zylob-b1v"/><path class="m_g9cerbk"/><path class="m0gubtb5o"/><path class="brnj5ubbo"/><path class="jkpms2b3a"/><path class="nmv-rksiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:clocks" /></template>
