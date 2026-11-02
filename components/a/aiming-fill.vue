<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcta-bc5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcta-bc5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:aiming-fill" /></template>
