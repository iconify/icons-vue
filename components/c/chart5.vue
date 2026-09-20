<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krspf2vus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krspf2vus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chart5" /></template>
