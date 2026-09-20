<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2p_948kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2p_948kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:checkmk" /></template>
