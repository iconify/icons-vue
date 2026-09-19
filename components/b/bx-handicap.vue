<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue0_fhfrg.css';
import '../../css/k/k794i539p.css';
import '../../css/p/p1ohgkcui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="ue0_fhfrg"/><path class="k794i539p"/><path class="p1ohgkcui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-handicap" /></template>
