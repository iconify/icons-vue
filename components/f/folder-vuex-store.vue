<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufv-l2b0j.css';
import '../../css/n/nu_6q77ce.css';
import '../../css/n/nrcaqmbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ufv-l2b0j"/><path class="nu_6q77ce"/><path class="nrcaqmbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-vuex-store" /></template>
