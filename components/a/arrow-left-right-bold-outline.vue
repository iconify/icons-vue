<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg3jmh0xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg3jmh0xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-left-right-bold-outline" /></template>
