<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asp2-2t9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asp2-2t9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cancel-circle-half-dot" /></template>
