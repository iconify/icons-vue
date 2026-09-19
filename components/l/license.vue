<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3g6y2-qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3g6y2-qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:license" /></template>
