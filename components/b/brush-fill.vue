<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsz7u7b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsz7u7b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:brush-fill" /></template>
