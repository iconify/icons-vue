<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9x7dzbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9x7dzbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-5-sharp" /></template>
