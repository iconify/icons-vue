<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fua-xp95i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fua-xp95i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-4-fill" /></template>
