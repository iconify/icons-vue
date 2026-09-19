<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt02hebku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nt02hebku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:calendar2-event-fill" /></template>
