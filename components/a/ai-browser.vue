<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0bu68h8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0bu68h8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-browser" /></template>
