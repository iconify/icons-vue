<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj_jdibkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj_jdibkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:head-side" /></template>
