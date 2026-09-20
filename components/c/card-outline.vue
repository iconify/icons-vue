<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha-pt9vny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha-pt9vny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:card-outline" /></template>
