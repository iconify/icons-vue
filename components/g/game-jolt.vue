<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kufh5zb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kufh5zb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:game-jolt" /></template>
