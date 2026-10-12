<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th4v1wbjr.css';
import '../../css/q/qydmu93ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th4v1wbjr"/><path class="qydmu93ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:graduation-cap-filled" /></template>
