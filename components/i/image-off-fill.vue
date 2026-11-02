<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enrlyzw_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enrlyzw_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:image-off-fill" /></template>
