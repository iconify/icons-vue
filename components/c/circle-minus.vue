<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmeomb9uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmeomb9uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:circle-minus" /></template>
