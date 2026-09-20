<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy96p8bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy96p8bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:btcmt" /></template>
