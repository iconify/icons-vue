<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dowbeobsa.css';
import '../../css/z/ziuz1w_mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dowbeobsa"/><path class="ziuz1w_mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:banknotepound" /></template>
