<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dic_g0bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dic_g0bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:badge-duotone" /></template>
