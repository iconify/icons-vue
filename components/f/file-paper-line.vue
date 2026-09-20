<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s03-lacgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s03-lacgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-paper-line" /></template>
