<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8mp0wbzm.css';
import '../../css/r/r1wj_pscx.css';
import '../../css/t/t8srk-ced.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m8mp0wbzm"/><path class="r1wj_pscx"/><path class="t8srk-ced"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:co2-storage-48" /></template>
