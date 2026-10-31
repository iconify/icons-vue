<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp9z4c-9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp9z4c-9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-right-small-bulk-round" /></template>
