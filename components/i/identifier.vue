<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_c1ujb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_c1ujb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:identifier" /></template>
