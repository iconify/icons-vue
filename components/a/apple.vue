<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlrchrjee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlrchrjee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:apple" /></template>
