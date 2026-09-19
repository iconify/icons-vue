<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w499r_bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w499r_bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-voice" /></template>
