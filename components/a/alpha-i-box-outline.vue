<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya2p9ecfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya2p9ecfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-i-box-outline" /></template>
