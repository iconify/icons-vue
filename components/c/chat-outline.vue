<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cws_mosnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cws_mosnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:chat-outline" /></template>
