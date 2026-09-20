<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxnsrcbjt.css';
import '../../css/u/uw344sgbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxnsrcbjt"/><path class="uw344sgbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:arrow-button-right-1-bold" /></template>
