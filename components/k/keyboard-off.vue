<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyw9u8buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyw9u8buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:keyboard-off" /></template>
