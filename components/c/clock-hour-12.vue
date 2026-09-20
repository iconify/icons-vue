<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y42q0rb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y42q0rb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clock-hour-12" /></template>
