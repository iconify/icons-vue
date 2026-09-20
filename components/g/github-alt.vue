<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfs7arb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfs7arb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:github-alt" /></template>
