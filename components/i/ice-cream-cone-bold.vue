<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr7tf6sse.css';
import '../../css/t/tf3fnbb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr7tf6sse"/><path class="tf3fnbb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:ice-cream-cone-bold" /></template>
