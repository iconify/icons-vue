<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqwry21cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqwry21cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:like" /></template>
