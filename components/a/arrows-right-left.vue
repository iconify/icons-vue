<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4sk3vb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4sk3vb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrows-right-left" /></template>
