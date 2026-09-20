<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ial_4vbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ial_4vbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:controller-round-right" /></template>
