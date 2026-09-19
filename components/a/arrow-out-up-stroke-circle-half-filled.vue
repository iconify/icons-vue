<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq32xccdr.css';
import '../../css/l/lm5rabblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq32xccdr"/><path class="lm5rabblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-up-stroke-circle-half-filled" /></template>
