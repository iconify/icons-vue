<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc4n74b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc4n74b5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-brain-01" /></template>
