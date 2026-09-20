<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcxdw0blf.css';
import '../../css/w/wue79tp2v.css';
import '../../css/n/nda_xfbmv.css';
import '../../css/r/rlm6af3qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kcxdw0blf"/><path class="wue79tp2v"/><path class="nda_xfbmv"/><path class="rlm6af3qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:equal" /></template>
