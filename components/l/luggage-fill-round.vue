<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwb58k66i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwb58k66i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:luggage-fill-round" /></template>
