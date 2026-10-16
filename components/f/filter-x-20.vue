<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok2n2nbsl.css';
import '../../css/q/q9_k86bve.css';
import '../../css/g/gfthn_qja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ok2n2nbsl"/><path class="q9_k86bve"/><path class="gfthn_qja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:filter-x-20" /></template>
