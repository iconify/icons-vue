<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp2h1tbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp2h1tbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:align-vertical" /></template>
