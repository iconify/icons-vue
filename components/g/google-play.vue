<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4d04xblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="v4d04xblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:google-play" /></template>
