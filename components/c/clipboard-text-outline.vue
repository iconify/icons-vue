<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfq19quzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfq19quzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-text-outline" /></template>
