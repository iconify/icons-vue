<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmdh-7bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmdh-7bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bench-back" /></template>
