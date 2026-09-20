<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km2dfdcao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km2dfdcao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:hair-dress-barber-bold" /></template>
