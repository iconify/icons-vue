<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi77ijbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi77ijbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clover-duocolor-round" /></template>
