<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/t_9g49b4u.css';
import '../../css/m/md286fbip.css';
import '../../css/a/ar2it4bxe.css';
import '../../css/t/twqas9b8h.css';
import '../../css/e/e07c_kbmv.css';
import '../../css/k/kd-8hzurr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="t_9g49b4u"/><g class="md286fbip"><path class="ar2it4bxe"/><path class="twqas9b8h"/><path class="e07c_kbmv"/><path class="kd-8hzurr"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:etc" /></template>
