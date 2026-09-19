<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erloabc9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erloabc9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chevron-down" /></template>
