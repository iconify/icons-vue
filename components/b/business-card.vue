<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0kaybcym.css';
import '../../css/l/l1wpyo1fg.css';
import '../../css/c/ciy1dsjbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0kaybcym"/><circle class="l1wpyo1fg"/><path class="ciy1dsjbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:business-card" /></template>
