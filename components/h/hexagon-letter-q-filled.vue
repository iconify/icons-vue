<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6977s0_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6977s0_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-letter-q-filled" /></template>
