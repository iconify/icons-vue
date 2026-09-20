<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7d6ijtcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7d6ijtcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keyboard-f4" /></template>
