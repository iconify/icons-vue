<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnri7s2ba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnri7s2ba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:grid-fill-round" /></template>
