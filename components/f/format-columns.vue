<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx9-le8ts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx9-le8ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-columns" /></template>
