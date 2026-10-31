<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j51q_13wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j51q_13wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:alarm-off-round" /></template>
