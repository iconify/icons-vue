<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd566n1tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd566n1tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrow-circle-left" /></template>
