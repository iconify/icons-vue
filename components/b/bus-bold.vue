<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az9avy84r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="az9avy84r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bus-bold" /></template>
