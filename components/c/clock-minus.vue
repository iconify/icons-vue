<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1kwljb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1kwljb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-minus" /></template>
