<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/go4gkqx7k.css';
import '../../css/x/x8qx25v3v.css';
import '../../css/o/oldcukbnq.css';
import '../../css/k/klfzlu_vz.css';
import '../../css/u/ujrkc1bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="go4gkqx7k wm-k"/><path class="wm-a x8qx25v3v"/><path class="oldcukbnq wm-shadow"/><path class="klfzlu_vz wm-k"/><path class="ujrkc1bmm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-monster-horns-engrave" /></template>
