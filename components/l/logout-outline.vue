<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiirhsbnc.css';
import '../../css/k/k-ib4_rmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iiirhsbnc"/><path clip-rule="evenodd" class="k-ib4_rmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:logout-outline" /></template>
