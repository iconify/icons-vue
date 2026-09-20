<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2bs-acjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m2bs-acjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lock-keyhole-unlocked-bold" /></template>
