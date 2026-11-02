<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9v2o4b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9v2o4b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ios-fill" /></template>
