<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9_1ckzyh.css';
import '../../css/z/zo4u7dbqx.css';
import '../../css/e/egb1_lbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="h9_1ckzyh"/><path class="zo4u7dbqx"/><path class="egb1_lbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbpad" /></template>
