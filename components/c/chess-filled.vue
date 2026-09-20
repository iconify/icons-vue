<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni4yygb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni4yygb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chess-filled" /></template>
