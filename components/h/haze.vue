<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2ownbcal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2ownbcal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:haze" /></template>
