<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trfqa1tba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trfqa1tba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:laurel-wreath-right-01" /></template>
