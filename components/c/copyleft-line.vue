<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxo6sslyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxo6sslyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copyleft-line" /></template>
