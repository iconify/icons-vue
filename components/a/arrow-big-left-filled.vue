<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efr7zvbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efr7zvbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:arrow-big-left-filled" /></template>
