<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol4q83bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol4q83bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brain-circuit-line" /></template>
