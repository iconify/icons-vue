<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed5yeem-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed5yeem-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:brackets-round" /></template>
