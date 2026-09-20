<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3vclip0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3vclip0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dagger" /></template>
