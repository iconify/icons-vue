<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmfytobta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmfytobta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:locate-fill-round" /></template>
