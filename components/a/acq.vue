<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcxdw0blf.css';
import '../../css/r/rsc1xgbvj.css';
import '../../css/n/nno8gebdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kcxdw0blf"/><path class="rsc1xgbvj"/><path class="nno8gebdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:acq" /></template>
