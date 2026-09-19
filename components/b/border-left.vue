<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhpnogbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhpnogbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:border-left" /></template>
