<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7ch0z4gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7ch0z4gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:lemonsqueezy" /></template>
