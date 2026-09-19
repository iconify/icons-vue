<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3r0drnxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q3r0drnxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:calendar3-event-fill" /></template>
