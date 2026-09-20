<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok8jdmbmr.css';
import '../../css/p/pgpjlbcjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ok8jdmbmr"/><path class="pgpjlbcjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:inpatient" /></template>
