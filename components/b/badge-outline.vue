<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er9ihbbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er9ihbbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:badge-outline" /></template>
