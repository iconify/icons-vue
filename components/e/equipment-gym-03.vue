<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtt7155uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtt7155uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:equipment-gym-03" /></template>
