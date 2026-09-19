<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uevae-bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uevae-bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:favourite" /></template>
