<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjzwxqm_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjzwxqm_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:direction-arrow-fill" /></template>
