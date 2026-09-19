<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub1ttxb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub1ttxb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:body-part-six-pack" /></template>
