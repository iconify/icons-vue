<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp16bptoo.css';
import '../../css/b/bi12bsetm.css';
import '../../css/o/o43-q11_n.css';
import '../../css/z/z21x_ohdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<mask id="flagpackGbEng0" width="32" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="rp16bptoo"/></mask><g clip-rule="evenodd" mask="url(#flagpackGbEng0)" class="bi12bsetm"><path class="o43-q11_n"/><path class="z21x_ohdt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:gb-eng" /></template>
