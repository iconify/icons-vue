<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljfx7hdpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljfx7hdpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:bus" /></template>
