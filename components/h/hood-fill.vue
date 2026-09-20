<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk4j0nbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk4j0nbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hood-fill" /></template>
