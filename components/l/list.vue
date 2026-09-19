<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr9tljbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qr9tljbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:list" /></template>
