<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3vv6gbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3vv6gbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:blush-brush-01" /></template>
