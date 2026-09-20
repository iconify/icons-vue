<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbydzgtjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbydzgtjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:check-active" /></template>
