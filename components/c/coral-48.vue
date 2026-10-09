<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by92osboh.css';
import '../../css/b/bt7ducbtn.css';
import '../../css/o/ops1169qo.css';
import '../../css/e/ew-rlnbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="by92osboh"/><path class="bt7ducbtn"/><path class="ops1169qo"/><path class="ew-rlnbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coral-48" /></template>
