<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8grogs4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8grogs4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:group-2-fill" /></template>
