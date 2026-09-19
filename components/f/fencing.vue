<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqg2_0b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqg2_0b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:fencing" /></template>
