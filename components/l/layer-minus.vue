<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty4zwew1b.css';
import '../../css/s/sar0t8bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty4zwew1b"/><path class="sar0t8bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:layer-minus" /></template>
