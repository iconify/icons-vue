<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sci_c0bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sci_c0bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dice-d8" /></template>
