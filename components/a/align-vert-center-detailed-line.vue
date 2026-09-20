<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3chf1bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3chf1bcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-vert-center-detailed-line" /></template>
