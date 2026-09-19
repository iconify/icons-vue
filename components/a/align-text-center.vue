<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id6c59bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id6c59bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:align-text-center" /></template>
