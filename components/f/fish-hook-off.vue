<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tku4xni9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tku4xni9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:fish-hook-off" /></template>
