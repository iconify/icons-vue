<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7q8mlb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q7q8mlb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:close-circle" /></template>
