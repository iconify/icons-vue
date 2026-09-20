<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtv-78cph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtv-78cph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:golf-tee" /></template>
