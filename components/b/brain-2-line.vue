<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijgpwoblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijgpwoblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:brain-2-line" /></template>
