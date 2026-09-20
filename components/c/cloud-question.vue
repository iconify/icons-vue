<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsh9etb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsh9etb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-question" /></template>
