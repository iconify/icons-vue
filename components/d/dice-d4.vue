<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbc-0cpda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbc-0cpda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dice-d4" /></template>
