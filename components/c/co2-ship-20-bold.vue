<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5uwqqndl.css';
import '../../css/a/a318uacfc.css';
import '../../css/u/ujn-tbcgw.css';
import '../../css/q/qcdgrwbvv.css';
import '../../css/n/nkzil-o-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o5uwqqndl"/><path class="a318uacfc"/><path class="ujn-tbcgw"/><path class="qcdgrwbvv"/><path class="nkzil-o-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:co2-ship-20-bold" /></template>
