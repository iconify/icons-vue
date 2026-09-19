<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd4_1pb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd4_1pb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:dice-3" /></template>
