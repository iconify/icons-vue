<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plg1gtjuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plg1gtjuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:cactus-fill" /></template>
