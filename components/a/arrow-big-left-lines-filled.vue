<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtrq_0lkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtrq_0lkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-big-left-lines-filled" /></template>
