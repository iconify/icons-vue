<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arbl_acfa.css';
import '../../css/j/jjurvxulj.css';
import '../../css/w/w3lw55b-f.css';
import '../../css/i/iii9vdbnp.css';
import '../../css/c/c2g-pd3xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="arbl_acfa"/><path class="jjurvxulj"/><path class="w3lw55b-f"/><path class="iii9vdbnp"/><path class="c2g-pd3xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-plugged-48-bold" /></template>
