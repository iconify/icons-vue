<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbcdme82c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbcdme82c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:list-music-filled" /></template>
