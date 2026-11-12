<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk63cfbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk63cfbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dreamcast" /></template>
