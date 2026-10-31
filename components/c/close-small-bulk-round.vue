<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w41rlbb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w41rlbb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:close-small-bulk-round" /></template>
