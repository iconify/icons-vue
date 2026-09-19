<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta2om1b3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ta2om1b3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:batteries-energy" /></template>
