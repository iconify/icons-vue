<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv4_ow18w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv4_ow18w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dice-3-fill" /></template>
