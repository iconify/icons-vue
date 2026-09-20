<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p80c_5d6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p80c_5d6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:fluxer" /></template>
