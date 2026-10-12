<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq6v1fb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq6v1fb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:align-horizontal-space-around-filled" /></template>
