<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whj_4pbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whj_4pbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:cake" /></template>
