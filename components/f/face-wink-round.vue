<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1h9_3gol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1h9_3gol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-wink-round" /></template>
