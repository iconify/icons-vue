<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3zsr3b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3zsr3b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:information-desk-symbol" /></template>
