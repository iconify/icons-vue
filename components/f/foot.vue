<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fanuthb_e.css';
import '../../css/u/um86nibse.css';
import '../../css/l/lco92fbia.css';
import '../../css/t/tw1l7nbgm.css';
import '../../css/o/oubjqlb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<circle class="fanuthb_e"/><circle class="um86nibse"/><circle class="lco92fbia"/><path class="tw1l7nbgm"/><circle class="oubjqlb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:foot" /></template>
