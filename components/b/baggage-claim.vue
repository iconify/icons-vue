<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaq_89bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vaq_89bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:baggage-claim" /></template>
