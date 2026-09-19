<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbxmv5lgw.css';
import '../../css/l/lbz_afxlg.css';
import '../../css/g/gc5bzfbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dbxmv5lgw"/><path class="lbz_afxlg"/><path class="gc5bzfbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:githubactions-wordmark" /></template>
