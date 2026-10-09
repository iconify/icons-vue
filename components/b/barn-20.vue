<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf8931yxd.css';
import '../../css/o/ohmm4ymdc.css';
import '../../css/x/x4owwtbzm.css';
import '../../css/z/zc_uuwb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kf8931yxd"/><path class="ohmm4ymdc"/><path class="x4owwtbzm"/><path class="zc_uuwb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:barn-20" /></template>
