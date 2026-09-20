<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haz8x-boa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haz8x-boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:border-vertical" /></template>
