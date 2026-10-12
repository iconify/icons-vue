<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i84x10b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i84x10b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:lamp-floor-filled" /></template>
