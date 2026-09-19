<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqgw987ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="kqgw987ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:hourglass-end" /></template>
