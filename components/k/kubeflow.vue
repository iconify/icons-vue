<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bose8-bou.css';
import '../../css/e/er-gjfemd.css';
import '../../css/y/yh97xd9ai.css';
import '../../css/z/zwbzsgbuk.css';
import '../../css/d/drcv5vb1v.css';
import '../../css/a/a3sbb9bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bose8-bou"/><path class="er-gjfemd"/><path class="yh97xd9ai"/><path class="zwbzsgbuk"/><path class="drcv5vb1v"/><path class="a3sbb9bcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kubeflow" /></template>
