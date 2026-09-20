<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp0lh4b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xp0lh4b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:certificate-success-filled" /></template>
