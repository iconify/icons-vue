<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2q6mpbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2q6mpbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:georgian-lari" /></template>
