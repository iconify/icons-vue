<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddzs-grco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddzs-grco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chess-king-filled" /></template>
