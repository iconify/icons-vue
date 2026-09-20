<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju4kv9bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju4kv9bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:beam" /></template>
