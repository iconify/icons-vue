<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckv68lbrl.css';
import '../../css/r/r_d7t_bew.css';
import '../../css/c/cg7d2pfom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckv68lbrl"/><circle class="r_d7t_bew"/><circle class="cg7d2pfom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:ghost" /></template>
