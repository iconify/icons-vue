<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl1ct9w7i.css';
import '../../css/c/cpisrvb2h.css';
import '../../css/z/z2jaifrlq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dl1ct9w7i"/><path class="cpisrvb2h"/><path class="z2jaifrlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-bowtie" /></template>
