<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhog2ktav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhog2ktav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:4-g-signal" /></template>
