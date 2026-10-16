<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0_0708wb.css';
import '../../css/b/b768ng9cg.css';
import '../../css/t/ttpih3a4n.css';
import '../../css/h/ht2kccogc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j0_0708wb"/><path class="b768ng9cg"/><path class="ttpih3a4n"/><path class="ht2kccogc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:growth-48" /></template>
