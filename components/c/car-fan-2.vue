<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-txrhc0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-txrhc0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:car-fan-2" /></template>
