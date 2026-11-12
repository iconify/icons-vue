<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhaiv-07w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhaiv-07w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-key" /></template>
