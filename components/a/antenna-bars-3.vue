<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfdzu3bdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfdzu3bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:antenna-bars-3" /></template>
