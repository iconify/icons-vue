<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byi38ackq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1600};
const content = `<path class="byi38ackq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:free-code-camp" /></template>
