<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9p9m8b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9p9m8b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-up-down-solid" /></template>
