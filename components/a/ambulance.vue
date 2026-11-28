<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb7ka-zms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb7ka-zms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:ambulance" /></template>
