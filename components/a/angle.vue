<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eers39bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eers39bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:angle" /></template>
