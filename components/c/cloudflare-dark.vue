<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr9qn8b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rr9qn8b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cloudflare-dark" /></template>
