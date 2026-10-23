<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxw52nabo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxw52nabo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:calendar-cog" /></template>
