<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kco8tpa1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kco8tpa1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:caret-down-circle" /></template>
