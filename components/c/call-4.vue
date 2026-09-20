<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slhw7xb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="slhw7xb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:call-4" /></template>
