<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9ken1ovu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9ken1ovu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:heat-wave-filled" /></template>
