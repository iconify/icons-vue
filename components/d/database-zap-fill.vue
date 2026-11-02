<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9kos04xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9kos04xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:database-zap-fill" /></template>
