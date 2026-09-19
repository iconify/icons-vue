<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rcnka6jzk.css';
import '../../css/m/md286fbip.css';
import '../../css/u/uqfwj2bsy.css';
import '../../css/k/kycke37ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="rcnka6jzk"/><g class="md286fbip"><path class="uqfwj2bsy"/><path class="kycke37ds"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:chain" /></template>
