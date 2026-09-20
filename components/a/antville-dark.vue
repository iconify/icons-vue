<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5fuocb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e5fuocb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:antville-dark" /></template>
