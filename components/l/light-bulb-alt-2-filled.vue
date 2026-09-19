<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-5eqqj4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-5eqqj4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:light-bulb-alt-2-filled" /></template>
