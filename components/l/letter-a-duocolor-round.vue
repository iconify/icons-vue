<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sprkijbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sprkijbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-a-duocolor-round" /></template>
