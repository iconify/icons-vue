<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfkv-rb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfkv-rb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bed-king-outline" /></template>
