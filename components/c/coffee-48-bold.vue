<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqabahbkv.css';
import '../../css/a/awqfydw7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rqabahbkv"/><path class="awqfydw7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coffee-48-bold" /></template>
