<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fetyxpbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fetyxpbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arch-filled" /></template>
