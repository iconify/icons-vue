<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll11jkzwr.css';
import '../../css/n/n7afpq_ej.css';
import '../../css/p/pjrgz1bag.css';
import '../../css/t/tgzu8obtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ll11jkzwr"/><path class="n7afpq_ej"/><path class="pjrgz1bag"/><path class="tgzu8obtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-vuepress" /></template>
