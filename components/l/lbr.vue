<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn_0otsqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn_0otsqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lbr" /></template>
