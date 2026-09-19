<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7i9ctbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7i9ctbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:home-04" /></template>
