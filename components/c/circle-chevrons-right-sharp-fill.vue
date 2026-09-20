<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thhopss1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thhopss1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-chevrons-right-sharp-fill" /></template>
