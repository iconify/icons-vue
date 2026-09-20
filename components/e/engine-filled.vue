<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2p38pb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2p38pb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:engine-filled" /></template>
