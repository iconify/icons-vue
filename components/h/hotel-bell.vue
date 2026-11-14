<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6x8pkw9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6x8pkw9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hotel-bell" /></template>
