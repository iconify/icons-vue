<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iao0xe98k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iao0xe98k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:france3" /></template>
