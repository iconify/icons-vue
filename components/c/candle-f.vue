<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsib2p_mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-1};
const content = `<path class="dsib2p_mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:candle-f" /></template>
