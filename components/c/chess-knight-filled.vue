<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sop8lzbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sop8lzbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chess-knight-filled" /></template>
