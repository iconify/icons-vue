<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgtagwbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgtagwbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:luggage-01" /></template>
