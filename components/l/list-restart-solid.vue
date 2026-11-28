<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy462fbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy462fbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:list-restart-solid" /></template>
