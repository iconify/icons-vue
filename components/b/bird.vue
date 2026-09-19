<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1uus8zrf.css';
import '../../css/z/zzmml7btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1uus8zrf"/><path class="zzmml7btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bird" /></template>
