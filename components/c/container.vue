<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnx8igb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnx8igb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:container" /></template>
