<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa4gzdbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa4gzdbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-right-short-sharp" /></template>
