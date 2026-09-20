<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2-x5cc0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2-x5cc0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bone-linear" /></template>
