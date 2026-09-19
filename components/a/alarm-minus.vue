<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-wfxjb1n.css';
import '../../css/f/fajrh4bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-wfxjb1n"/><path class="fajrh4bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alarm-minus" /></template>
