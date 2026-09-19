<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2wzqxngm.css';
import '../../css/b/bb_4oobxv.css';
import '../../css/e/ej16q4bjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d2wzqxngm"/><path class="bb_4oobxv"/><path class="ej16q4bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:expand" /></template>
