<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8x6l9lic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8x6l9lic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:curtains" /></template>
