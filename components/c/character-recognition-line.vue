<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_h2e2boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_h2e2boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:character-recognition-line" /></template>
