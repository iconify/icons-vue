<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh_nadcab.css';
import '../../css/u/ub4d63l7m.css';
import '../../css/k/k43y_he5a.css';
import '../../css/k/kaisiyc_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gh_nadcab"/><circle class="ub4d63l7m"/><circle class="k43y_he5a"/><path class="kaisiyc_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:carbon-for-ibm-dotcom" /></template>
