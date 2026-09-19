<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah05wvbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah05wvbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:atres-player" /></template>
