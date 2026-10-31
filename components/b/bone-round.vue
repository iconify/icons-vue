<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq34xl16r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq34xl16r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bone-round" /></template>
