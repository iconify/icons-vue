<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghqo2s4pq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghqo2s4pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:clipboard-plus-solid" /></template>
