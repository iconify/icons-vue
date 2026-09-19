<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc3tj3bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc3tj3bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:airgradient-one" /></template>
