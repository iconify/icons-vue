<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwombobzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwombobzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bolt-square-filled" /></template>
