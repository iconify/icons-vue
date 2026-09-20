<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx662ub-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx662ub-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-briefcase-line" /></template>
