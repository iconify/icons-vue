<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byn1rl6tp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byn1rl6tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bell-remove-outline" /></template>
