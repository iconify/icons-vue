<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua9_ryb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua9_ryb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hand-off" /></template>
