<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6mu4cbgx.css';
import '../../css/e/eqj_f_bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v6mu4cbgx"/><path class="eqj_f_bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chain-20" /></template>
