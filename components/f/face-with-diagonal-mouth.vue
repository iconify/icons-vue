<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_ywjjbch.css';
import '../../css/h/hrsbdbc-d.css';
import '../../css/e/e-qaj9bzm.css';
import '../../css/a/a50a-ab_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="k_ywjjbch"/><circle class="hrsbdbc-d"/><path class="e-qaj9bzm"/><path class="a50a-ab_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:face-with-diagonal-mouth" /></template>
