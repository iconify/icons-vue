<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyf3pjg2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyf3pjg2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-lightning-fill-round" /></template>
