<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4py13b7f.css';
import '../../css/s/s4volvbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4py13b7f"/><path class="s4volvbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:arrow-up" /></template>
