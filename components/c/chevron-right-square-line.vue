<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myz8czrep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myz8czrep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:chevron-right-square-line" /></template>
