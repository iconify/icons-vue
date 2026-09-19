<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ompke7h3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ompke7h3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:gallery-vertical-end" /></template>
