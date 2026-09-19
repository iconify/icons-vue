<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_6hphyay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_6hphyay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:comic-bubble-filled" /></template>
