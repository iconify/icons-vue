<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8nkvgzbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8nkvgzbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoji-cow" /></template>
