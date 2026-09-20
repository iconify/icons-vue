<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxxah85-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxxah85-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-down-right-from-circle" /></template>
