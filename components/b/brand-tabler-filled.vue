<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrqn8np3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrqn8np3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-tabler-filled" /></template>
