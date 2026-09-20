<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv024--aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv024--aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:counter-strike" /></template>
