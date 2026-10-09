<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-vsuachh.css';
import '../../css/a/at10t5btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q-vsuachh"/><path class="at10t5btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heading-20-bold" /></template>
