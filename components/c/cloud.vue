<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hia-se2uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hia-se2uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:cloud" /></template>
