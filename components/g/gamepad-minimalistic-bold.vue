<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb74pc30f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qb74pc30f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gamepad-minimalistic-bold" /></template>
