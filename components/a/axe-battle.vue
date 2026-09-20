<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijj70j92x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijj70j92x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:axe-battle" /></template>
