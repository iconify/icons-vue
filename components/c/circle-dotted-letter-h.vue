<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9kuzwb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9kuzwb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dotted-letter-h" /></template>
