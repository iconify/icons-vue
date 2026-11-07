<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lahr7gp7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lahr7gp7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fire-minimalistic-linear" /></template>
