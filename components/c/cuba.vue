<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlhn8ybms.css';
import '../../css/k/k1cse-ckm.css';
import '../../css/i/ik5eqpb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="vlhn8ybms"/><path class="k1cse-ckm"/><path class="ik5eqpb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:cuba" /></template>
