<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnjtahbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnjtahbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:droplet-round" /></template>
