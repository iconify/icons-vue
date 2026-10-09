<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2dc9v3fg.css';
import '../../css/j/jwps220zj.css';
import '../../css/b/bdd_6-bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x2dc9v3fg"/><path class="jwps220zj"/><path class="bdd_6-bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crew-transfer-vessel-48-bold" /></template>
