<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o39gc1beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o39gc1beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:knexdotjs" /></template>
