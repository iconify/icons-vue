<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7ls2g-va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7ls2g-va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-discord-alt" /></template>
