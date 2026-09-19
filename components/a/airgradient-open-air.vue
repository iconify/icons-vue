<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f82k84b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f82k84b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:airgradient-open-air" /></template>
