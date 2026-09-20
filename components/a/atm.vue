<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2ckhrb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="n2ckhrb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:atm" /></template>
